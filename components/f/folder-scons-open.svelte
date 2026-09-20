<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhjw5tknw.css';
import '../../css/a/a98ziyr1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hhjw5tknw"/><path class="a98ziyr1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-scons-open" {...props}></Icon>
