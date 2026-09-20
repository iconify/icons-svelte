<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgssn1xut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgssn1xut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-2-line" {...props}></Icon>
