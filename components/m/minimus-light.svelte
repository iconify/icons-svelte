<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auggvy6li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="auggvy6li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minimus-light" {...props}></Icon>
