<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf_lw1akt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf_lw1akt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:auto-awesome-outline" {...props}></Icon>
