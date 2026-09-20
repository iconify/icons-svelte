<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkw2z3lzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkw2z3lzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:plus-secure" {...props}></Icon>
