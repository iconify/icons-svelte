<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_f4z8bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_f4z8bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:alacritty-alt" {...props}></Icon>
