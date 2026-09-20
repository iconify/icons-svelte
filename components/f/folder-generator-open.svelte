<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhjw5tknw.css';
import '../../css/i/iph07lbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hhjw5tknw"/><path class="iph07lbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-generator-open" {...props}></Icon>
