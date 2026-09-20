<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3vz8ibep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3vz8ibep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:autodesk-logo-1-block" {...props}></Icon>
