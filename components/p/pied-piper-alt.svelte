<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhdgbeb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="mhdgbeb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:pied-piper-alt" {...props}></Icon>
