<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqsk4dbaf.css';
import '../../css/b/b8ymvlblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tqsk4dbaf"/><path class="b8ymvlblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-album-cd-disk-playlist" {...props}></Icon>
