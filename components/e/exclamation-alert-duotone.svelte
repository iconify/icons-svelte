<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vla37tbfm.css';
import '../../css/v/vhe-a2h2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vla37tbfm"/><path class="vhe-a2h2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:exclamation-alert-duotone" {...props}></Icon>
