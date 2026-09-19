<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymxvme3fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ymxvme3fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:light-alarm" {...props}></Icon>
