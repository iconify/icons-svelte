<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj2u3m68c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj2u3m68c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-sync-corner-round" {...props}></Icon>
