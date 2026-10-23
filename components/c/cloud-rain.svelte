<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djdd0mbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djdd0mbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloud-rain" {...props}></Icon>
