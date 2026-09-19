<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y96k3lb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y96k3lb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:insert-table-alt-outline" {...props}></Icon>
