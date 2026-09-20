<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7y0-7c0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7y0-7c0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:alternativeto" {...props}></Icon>
