<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i026q6bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i026q6bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:door-open-sharp" {...props}></Icon>
