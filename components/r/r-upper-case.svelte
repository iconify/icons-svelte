<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-ixh8fnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":471,"height":735};
const content = `<path class="u-ixh8fnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:r-upper-case" {...props}></Icon>
