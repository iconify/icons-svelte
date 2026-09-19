<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-pk2evut.css';
import '../../css/m/mxwo3o_cb.css';
import '../../css/v/v01vscs4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i-pk2evut"/><path class="mxwo3o_cb"/><path class="v01vscs4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:office-building" {...props}></Icon>
