<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwjci56pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cwjci56pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crowdsec-manager-dark" {...props}></Icon>
