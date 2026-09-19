<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myy2k-mkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="myy2k-mkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:largeredcircle" {...props}></Icon>
