<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flwcn99fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="flwcn99fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crowdsec-manager" {...props}></Icon>
