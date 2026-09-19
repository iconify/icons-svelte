<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpe5don3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpe5don3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:peppers" {...props}></Icon>
