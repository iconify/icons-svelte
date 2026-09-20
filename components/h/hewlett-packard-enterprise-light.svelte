<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrpt4zbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hrpt4zbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hewlett-packard-enterprise-light" {...props}></Icon>
