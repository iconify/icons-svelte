<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wff71wb4h.css';
import '../../css/t/t01rqxb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wff71wb4h"/><path class="t01rqxb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-superset-dark" {...props}></Icon>
