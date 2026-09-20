<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2ehebbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t2ehebbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kanidm-dark" {...props}></Icon>
