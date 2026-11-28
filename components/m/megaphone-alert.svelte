<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atseoh4ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atseoh4ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:megaphone-alert" {...props}></Icon>
