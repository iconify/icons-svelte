<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxxup7lke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fxxup7lke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:poeticmetric-dark" {...props}></Icon>
