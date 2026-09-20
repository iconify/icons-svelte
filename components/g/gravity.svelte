<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj7t9lb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj7t9lb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gravity" {...props}></Icon>
