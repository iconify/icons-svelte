<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s37u5-ydv.css';
import '../../css/m/m3pjiwe1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s37u5-ydv"/><path class="m3pjiwe1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-nuxt-open" {...props}></Icon>
