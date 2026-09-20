<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx73xpb2j.css';
import '../../css/i/i-yovpx2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx73xpb2j"/><path class="i-yovpx2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:key-asterisk-24" {...props}></Icon>
