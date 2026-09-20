<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjwj45jme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjwj45jme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-left-light" {...props}></Icon>
