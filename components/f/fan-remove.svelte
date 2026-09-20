<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k55_vi-il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k55_vi-il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fan-remove" {...props}></Icon>
