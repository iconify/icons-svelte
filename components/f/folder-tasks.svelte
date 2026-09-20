<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6cjc0bct.css';
import '../../css/c/cr1evbbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v6cjc0bct"/><path class="cr1evbbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-tasks" {...props}></Icon>
