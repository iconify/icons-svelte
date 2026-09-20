<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh5j824-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh5j824-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:links-line" {...props}></Icon>
