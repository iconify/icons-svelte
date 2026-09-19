<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meu8qvatp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="meu8qvatp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:bell" {...props}></Icon>
