<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdrm33fiz.css';
import '../../css/w/we0aawlvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kdrm33fiz"/><path class="we0aawlvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-components-open" {...props}></Icon>
