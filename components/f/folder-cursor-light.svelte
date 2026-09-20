<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz4v91hwj.css';
import '../../css/l/lhr648d7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gz4v91hwj"/><path class="lhr648d7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-cursor-light" {...props}></Icon>
