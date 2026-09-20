<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itr6d0bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="itr6d0bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:okd-dark" {...props}></Icon>
