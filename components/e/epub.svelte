<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-lnz7bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a-lnz7bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:epub" {...props}></Icon>
