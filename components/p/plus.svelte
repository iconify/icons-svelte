<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inpw15gqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="inpw15gqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:plus" {...props}></Icon>
