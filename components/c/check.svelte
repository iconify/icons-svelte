<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htbxum14x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="htbxum14x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:check" {...props}></Icon>
