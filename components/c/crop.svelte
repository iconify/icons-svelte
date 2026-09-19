<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i64wucb0q.css';
import '../../css/q/qryw2o0qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i64wucb0q"/><path class="qryw2o0qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:crop" {...props}></Icon>
