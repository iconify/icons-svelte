<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_4qsubgk.css';
import '../../css/o/omqgt0bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_4qsubgk"/><path class="omqgt0bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:phone-call" {...props}></Icon>
