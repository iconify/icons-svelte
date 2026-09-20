<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atvq_qble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atvq_qble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pin-24" {...props}></Icon>
