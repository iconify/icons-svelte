<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8w8v-egj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z8w8v-egj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-acrobat-dark" {...props}></Icon>
