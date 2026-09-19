<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfmt0acwz.css';
import '../../css/t/tc0qvy92q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfmt0acwz"/><path class="tc0qvy92q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:building-small" {...props}></Icon>
