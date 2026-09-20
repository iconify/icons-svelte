<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5fxn4-5j.css';
import '../../css/q/q1b8t8b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i5fxn4-5j"/><path class="q1b8t8b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-azure-pipelines" {...props}></Icon>
