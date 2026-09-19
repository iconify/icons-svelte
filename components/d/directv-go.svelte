<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlcb11blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlcb11blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:directv-go" {...props}></Icon>
