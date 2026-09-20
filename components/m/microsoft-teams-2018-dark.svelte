<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e78tupbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e78tupbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-teams-2018-dark" {...props}></Icon>
