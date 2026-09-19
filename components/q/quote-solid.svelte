<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imoh3dbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="imoh3dbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:quote-solid" {...props}></Icon>
