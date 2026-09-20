<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-8oskmsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-8oskmsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:camera" {...props}></Icon>
