<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z53j1gsut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z53j1gsut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:progressive-dark" {...props}></Icon>
