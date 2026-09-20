<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_4c-ac4q.css';
import '../../css/x/xb829869a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f_4c-ac4q"/><path class="xb829869a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-terraform-open" {...props}></Icon>
