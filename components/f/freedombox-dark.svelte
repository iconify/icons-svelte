<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loj74m4-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="loj74m4-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freedombox-dark" {...props}></Icon>
