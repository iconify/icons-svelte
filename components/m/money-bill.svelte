<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyb7ezbvr.css';
import '../../css/g/g_zlf0bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyb7ezbvr"/><circle class="g_zlf0bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:money-bill" {...props}></Icon>
