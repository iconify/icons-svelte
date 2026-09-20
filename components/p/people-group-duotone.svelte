<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xce_36ygs.css';
import '../../css/u/u6urlybip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xce_36ygs"/><path class="u6urlybip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:people-group-duotone" {...props}></Icon>
