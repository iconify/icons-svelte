<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5n9agbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b5n9agbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-mp3" {...props}></Icon>
