<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjlq3pbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjlq3pbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-x" {...props}></Icon>
