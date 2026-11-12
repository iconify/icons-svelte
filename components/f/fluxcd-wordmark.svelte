<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu-95fbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nu-95fbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:fluxcd-wordmark" {...props}></Icon>
