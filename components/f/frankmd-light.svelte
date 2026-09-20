<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy8dm9bqf.css';
import '../../css/h/hdhbc3z4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sy8dm9bqf"/><path class="hdhbc3z4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frankmd-light" {...props}></Icon>
