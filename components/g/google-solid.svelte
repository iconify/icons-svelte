<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdc5hdbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hdc5hdbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:google-solid" {...props}></Icon>
