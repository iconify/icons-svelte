<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qym-qrooz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qym-qrooz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-teams-2016-dark" {...props}></Icon>
