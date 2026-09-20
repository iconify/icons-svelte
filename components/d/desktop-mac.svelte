<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnrsmjtgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnrsmjtgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:desktop-mac" {...props}></Icon>
