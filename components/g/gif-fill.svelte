<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz64ambus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz64ambus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:gif-fill" {...props}></Icon>
