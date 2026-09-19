<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsyxn_5xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="vsyxn_5xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:playstation" {...props}></Icon>
