<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in7n1d18z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="in7n1d18z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:hospital-sign-remix" {...props}></Icon>
