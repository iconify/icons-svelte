<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8v230bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8v230bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:exchange" {...props}></Icon>
