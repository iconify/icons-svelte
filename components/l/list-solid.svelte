<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx2k_ybxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tx2k_ybxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:list-solid" {...props}></Icon>
