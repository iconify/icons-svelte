<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w01qysb_c.css';
import '../../css/c/c2wp6ritf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="w01qysb_c"/><path class="c2wp6ritf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flood" {...props}></Icon>
