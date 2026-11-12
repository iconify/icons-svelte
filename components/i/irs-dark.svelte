<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfwme05gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfwme05gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:irs-dark" {...props}></Icon>
