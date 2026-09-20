<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv_c0-59u.css';
import '../../css/w/whz7b1b5h.css';
import '../../css/m/m4ht6ksod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wv_c0-59u"/><path class="whz7b1b5h"/><path class="m4ht6ksod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kchat-light" {...props}></Icon>
