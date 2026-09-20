<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oga4-ybii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oga4-ybii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:replane-light" {...props}></Icon>
