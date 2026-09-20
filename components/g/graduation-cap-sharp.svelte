<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8f_ihw3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8f_ihw3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:graduation-cap-sharp" {...props}></Icon>
