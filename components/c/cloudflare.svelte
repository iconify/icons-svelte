<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn76znsys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tn76znsys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cloudflare" {...props}></Icon>
