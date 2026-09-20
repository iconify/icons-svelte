<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns8xnbbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ns8xnbbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:photopea" {...props}></Icon>
