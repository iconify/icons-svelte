<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq3zh6b0i.css';
import '../../css/f/f8da0bkqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oq3zh6b0i"/><path class="f8da0bkqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-mail-light" {...props}></Icon>
