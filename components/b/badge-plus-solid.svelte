<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0pnhbbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0pnhbbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-plus-solid" {...props}></Icon>
