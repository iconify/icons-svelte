<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkufbknyv.css';
import '../../css/s/s7hlo9zxp.css';
import '../../css/g/gbfxncsks.css';
import '../../css/e/eentqmb8a.css';
import '../../css/f/f9ffv5bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jkufbknyv"/><path class="s7hlo9zxp"/><path class="gbfxncsks"/><path class="eentqmb8a"/><path class="f9ffv5bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quire-ink" {...props}></Icon>
