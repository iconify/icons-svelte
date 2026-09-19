<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8d3bcc7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8d3bcc7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:bluetooth-fill" {...props}></Icon>
