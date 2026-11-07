<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5ogxjm1y.css';
import '../../css/o/oiqop8ebf.css';
import '../../css/p/p8bolj64l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5ogxjm1y"/><path class="oiqop8ebf"/><path class="p8bolj64l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-close-bold-duotone" {...props}></Icon>
