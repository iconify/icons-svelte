<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/capfaguaf.css';
import '../../css/a/atabikbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="capfaguaf"/><path class="atabikbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:link" {...props}></Icon>
