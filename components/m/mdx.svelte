<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkac_gbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bkac_gbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:mdx" {...props}></Icon>
