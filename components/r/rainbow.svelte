<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb5k4m7rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="mb5k4m7rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:rainbow" {...props}></Icon>
