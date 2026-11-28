<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hie7b5bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hie7b5bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:plane-check" {...props}></Icon>
