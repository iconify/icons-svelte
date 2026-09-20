<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am5ozhb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am5ozhb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:beaker-outline" {...props}></Icon>
