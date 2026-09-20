<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8rt5bbrs.css';
import '../../css/a/ad8jx5snz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y8rt5bbrs"/><path class="ad8jx5snz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-console-open" {...props}></Icon>
