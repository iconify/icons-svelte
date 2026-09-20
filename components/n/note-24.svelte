<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cle0u0bwz.css';
import '../../css/e/e1s56dbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cle0u0bwz"/><path class="e1s56dbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:note-24" {...props}></Icon>
