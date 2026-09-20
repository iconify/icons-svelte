<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps-bh4bky.css';
import '../../css/w/w71itubsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ps-bh4bky"/><path class="w71itubsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-expo-open" {...props}></Icon>
