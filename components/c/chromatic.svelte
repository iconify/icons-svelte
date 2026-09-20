<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcefzjfcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bcefzjfcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:chromatic" {...props}></Icon>
