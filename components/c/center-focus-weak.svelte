<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id_2uy04o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="id_2uy04o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:center-focus-weak" {...props}></Icon>
