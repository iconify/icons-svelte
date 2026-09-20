<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qim_7oblv.css';
import '../../css/a/as36oyixv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qim_7oblv"/><path class="as36oyixv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cog-light" {...props}></Icon>
