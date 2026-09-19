<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhdau5_nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="dhdau5_nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:font-awesome-alt" {...props}></Icon>
