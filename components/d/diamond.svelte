<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f333e122z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f333e122z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:diamond" {...props}></Icon>
