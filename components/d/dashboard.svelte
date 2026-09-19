<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydfp0pbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydfp0pbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:dashboard" {...props}></Icon>
