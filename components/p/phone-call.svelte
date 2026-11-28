<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p445uz47x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p445uz47x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:phone-call" {...props}></Icon>
