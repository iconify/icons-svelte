<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-cz3x_bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="x-cz3x_bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dolly" {...props}></Icon>
