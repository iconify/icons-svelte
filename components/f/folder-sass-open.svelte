<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhri5rpkp.css';
import '../../css/r/rr671wplb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uhri5rpkp"/><path class="rr671wplb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-sass-open" {...props}></Icon>
