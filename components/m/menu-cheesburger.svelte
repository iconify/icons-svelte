<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1m7xcchj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="a1m7xcchj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:menu-cheesburger" {...props}></Icon>
