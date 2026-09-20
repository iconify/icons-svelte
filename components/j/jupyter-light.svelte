<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygxvezb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygxvezb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jupyter-light" {...props}></Icon>
