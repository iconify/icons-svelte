<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spb1f5bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spb1f5bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:burger" {...props}></Icon>
