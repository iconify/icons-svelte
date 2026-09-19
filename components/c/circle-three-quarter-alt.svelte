<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt6wxsl1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt6wxsl1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-three-quarter-alt" {...props}></Icon>
