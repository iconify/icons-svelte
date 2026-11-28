<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-k6v8bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-k6v8bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:flag" {...props}></Icon>
