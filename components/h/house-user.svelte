<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km1ktek-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="km1ktek-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:house-user" {...props}></Icon>
