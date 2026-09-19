<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z916odbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z916odbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plug-fill-12" {...props}></Icon>
