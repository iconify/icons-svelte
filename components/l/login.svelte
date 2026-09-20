<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni0-8obrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni0-8obrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:login" {...props}></Icon>
