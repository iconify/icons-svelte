<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh-r6ubyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh-r6ubyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hot-air-balloon" {...props}></Icon>
