<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxji0o-1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vxji0o-1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nuxt" {...props}></Icon>
