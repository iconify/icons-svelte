<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf-c3ibdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gf-c3ibdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-music-fill" {...props}></Icon>
