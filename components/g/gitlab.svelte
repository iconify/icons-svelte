<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vply4ib2u.css';
import '../../css/e/eea_i9bnw.css';
import '../../css/x/xz2rsdmzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vply4ib2u"/><path class="eea_i9bnw"/><path class="xz2rsdmzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitlab" {...props}></Icon>
