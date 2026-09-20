<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nis8n537v.css';
import '../../css/s/s-upr6ely.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nis8n537v"/><path class="s-upr6ely"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:markdoc-config" {...props}></Icon>
