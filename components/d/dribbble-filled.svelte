<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cek003ruh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cek003ruh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:dribbble-filled" {...props}></Icon>
