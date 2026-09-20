<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr3mles8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr3mles8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:biscuit-edit" {...props}></Icon>
