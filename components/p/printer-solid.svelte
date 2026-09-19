<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cep-q2bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cep-q2bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:printer-solid" {...props}></Icon>
