<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o57oqtj-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o57oqtj-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-rocket" {...props}></Icon>
