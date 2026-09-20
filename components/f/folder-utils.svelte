<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5evchskr.css';
import '../../css/q/qa0jhaboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a5evchskr"/><path class="qa0jhaboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-utils" {...props}></Icon>
