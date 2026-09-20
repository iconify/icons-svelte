<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_mebygut.css';
import '../../css/j/jmg8jub9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i_mebygut"/><path class="jmg8jub9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-note-music" {...props}></Icon>
