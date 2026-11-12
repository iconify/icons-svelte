<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-6ltbboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d-6ltbboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kanidm-dark" {...props}></Icon>
