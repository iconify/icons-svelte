<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm9ghmktn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nm9ghmktn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dazn-dark" {...props}></Icon>
