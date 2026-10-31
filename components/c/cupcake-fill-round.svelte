<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9hw2oe0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9hw2oe0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cupcake-fill-round" {...props}></Icon>
