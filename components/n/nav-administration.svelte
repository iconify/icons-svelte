<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-da5wbxh.css';
import '../../css/h/h1p0vrb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n-da5wbxh"/><path clip-rule="evenodd" class="h1p0vrb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-administration" {...props}></Icon>
