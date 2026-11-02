<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0583u-ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0583u-ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-down-circle-line" {...props}></Icon>
