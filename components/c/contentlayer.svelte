<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twg23usft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" transform="matrix(.5949 0 0 .61208 9.182 1.311)" class="twg23usft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:contentlayer" {...props}></Icon>
