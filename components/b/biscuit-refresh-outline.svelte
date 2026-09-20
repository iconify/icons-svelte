<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-2-_i5gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-2-_i5gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:biscuit-refresh-outline" {...props}></Icon>
