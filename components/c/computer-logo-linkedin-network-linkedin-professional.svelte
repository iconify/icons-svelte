<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1db_x1ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a1db_x1ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-logo-linkedin-network-linkedin-professional" {...props}></Icon>
