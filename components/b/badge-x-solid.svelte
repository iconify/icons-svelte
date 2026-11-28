<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu5tysbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu5tysbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-x-solid" {...props}></Icon>
