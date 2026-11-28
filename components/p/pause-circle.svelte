<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guifg13yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guifg13yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pause-circle" {...props}></Icon>
