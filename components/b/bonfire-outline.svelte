<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dworj5m2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dworj5m2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bonfire-outline" {...props}></Icon>
