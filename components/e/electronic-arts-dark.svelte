<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwgz_dbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cwgz_dbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:electronic-arts-dark" {...props}></Icon>
