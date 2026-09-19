<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj43_vuli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qj43_vuli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:eye-slash" {...props}></Icon>
