<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fubs2opfz.css';
import '../../css/q/qxbtx8ztn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fubs2opfz"/><path class="qxbtx8ztn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:producthunt" {...props}></Icon>
