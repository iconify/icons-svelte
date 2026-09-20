<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7bh2fp3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h7bh2fp3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:appwrite" {...props}></Icon>
