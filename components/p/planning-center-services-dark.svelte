<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjkg1xcso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjkg1xcso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-services-dark" {...props}></Icon>
