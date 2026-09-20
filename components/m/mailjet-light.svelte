<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6a744bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o6a744bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailjet-light" {...props}></Icon>
