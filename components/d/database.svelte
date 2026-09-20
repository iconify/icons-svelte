<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw7jrfk5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw7jrfk5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:database" {...props}></Icon>
