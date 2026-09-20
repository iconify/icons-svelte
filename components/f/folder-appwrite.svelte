<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u64rmvb8r.css';
import '../../css/i/iz42m8brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u64rmvb8r"/><path class="iz42m8brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-appwrite" {...props}></Icon>
