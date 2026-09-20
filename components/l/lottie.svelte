<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhnry8e_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bhnry8e_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lottie" {...props}></Icon>
