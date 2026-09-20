<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9e8afbxf.css';
import '../../css/y/ye6rbxb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i9e8afbxf"/><path class="ye6rbxb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:gradle" {...props}></Icon>
