<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvj5dzbtl.css';
import '../../css/i/inpc4rroq.css';
import '../../css/q/qapg4nbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvj5dzbtl"/><path class="inpc4rroq"/><path clip-rule="evenodd" class="qapg4nbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fer" {...props}></Icon>
