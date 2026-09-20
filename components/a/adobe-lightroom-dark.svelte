<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3n6v8ksz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3n6v8ksz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-lightroom-dark" {...props}></Icon>
