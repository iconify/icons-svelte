<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vevo467ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vevo467ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-image-solid" {...props}></Icon>
