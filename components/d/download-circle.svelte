<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abgf9lb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abgf9lb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:download-circle" {...props}></Icon>
