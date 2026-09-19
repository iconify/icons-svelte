<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chs_wwive.css';
import '../../css/d/d4xm7xbec.css';
import '../../css/z/z1hhkczws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="chs_wwive"/><path class="d4xm7xbec"/><path class="z1hhkczws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:packer-wordmark" {...props}></Icon>
