<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytbpjhtjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytbpjhtjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bread-slice-outline" {...props}></Icon>
