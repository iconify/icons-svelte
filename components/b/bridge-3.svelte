<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8zu3ni0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m8zu3ni0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bridge-3" {...props}></Icon>
