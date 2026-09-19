<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgvm7gdme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgvm7gdme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:male-sign" {...props}></Icon>
