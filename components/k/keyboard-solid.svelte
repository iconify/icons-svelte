<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf6h0-b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf6h0-b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:keyboard-solid" {...props}></Icon>
