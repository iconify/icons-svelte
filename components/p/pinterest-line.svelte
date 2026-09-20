<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0yqp85dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0yqp85dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pinterest-line" {...props}></Icon>
