<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi9dnccku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi9dnccku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:check-filled" {...props}></Icon>
