<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb-gssxxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gb-gssxxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:label" {...props}></Icon>
