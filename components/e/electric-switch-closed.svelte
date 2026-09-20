<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9dhulbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9dhulbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:electric-switch-closed" {...props}></Icon>
