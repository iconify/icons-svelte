<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoyaqe29i.css';
import '../../css/b/bd7gnab7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eoyaqe29i"/><path class="bd7gnab7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dope-security" {...props}></Icon>
