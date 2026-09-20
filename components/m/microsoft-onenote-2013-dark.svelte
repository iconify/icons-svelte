<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puhh1sths.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="puhh1sths"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-onenote-2013-dark" {...props}></Icon>
