<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz86kxbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lz86kxbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:location-check-solid" {...props}></Icon>
