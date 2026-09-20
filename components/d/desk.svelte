<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abk7cacez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abk7cacez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:desk" {...props}></Icon>
