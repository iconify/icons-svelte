<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6s6ebbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u6s6ebbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:espocrm-dark" {...props}></Icon>
