<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hch5jjbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hch5jjbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:clock-solid" {...props}></Icon>
