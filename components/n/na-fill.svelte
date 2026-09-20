<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-v6je9ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-v6je9ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:na-fill" {...props}></Icon>
