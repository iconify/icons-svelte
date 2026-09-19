<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tydndxb5d.css';
import '../../css/f/fjomncsfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tydndxb5d"/><path class="fjomncsfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:camera" {...props}></Icon>
