<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imklbhx5a.css';
import '../../css/g/g2u40lrig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imklbhx5a"/><path class="g2u40lrig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:currency-euro-bubble" {...props}></Icon>
