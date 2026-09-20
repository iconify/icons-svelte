<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_4c-ac4q.css';
import '../../css/c/cr1evbbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f_4c-ac4q"/><path class="cr1evbbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-tasks-open" {...props}></Icon>
