<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biwmr-bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="biwmr-bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:education-outline" {...props}></Icon>
