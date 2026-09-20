<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp68ljb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lp68ljb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homer-light" {...props}></Icon>
