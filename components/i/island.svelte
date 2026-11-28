<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm6oswlyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm6oswlyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:island" {...props}></Icon>
