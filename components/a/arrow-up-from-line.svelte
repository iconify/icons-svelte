<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn6l8cb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn6l8cb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-from-line" {...props}></Icon>
