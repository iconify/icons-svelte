<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlcinebpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlcinebpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-d10-solid" {...props}></Icon>
