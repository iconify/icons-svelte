<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zchwa-b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zchwa-b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:hourglass-solid" {...props}></Icon>
