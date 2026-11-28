<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijm667k2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijm667k2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plus-circle-solid" {...props}></Icon>
