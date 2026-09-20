<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf8n7mb7y.css';
import '../../css/z/zcurb14eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wf8n7mb7y"/><path class="zcurb14eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jeedom" {...props}></Icon>
