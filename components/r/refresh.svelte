<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0i14acnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0i14acnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:refresh" {...props}></Icon>
