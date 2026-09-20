<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia6arpbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ia6arpbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:information-outline" {...props}></Icon>
