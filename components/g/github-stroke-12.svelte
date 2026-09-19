<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq9yo4btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="eq9yo4btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:github-stroke-12" {...props}></Icon>
