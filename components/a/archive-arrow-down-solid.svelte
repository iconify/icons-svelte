<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1bgs2boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h1bgs2boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:archive-arrow-down-solid" {...props}></Icon>
