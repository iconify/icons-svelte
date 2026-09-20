<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzk0y1b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzk0y1b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-minus" {...props}></Icon>
