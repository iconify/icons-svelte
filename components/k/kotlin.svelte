<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qea20536a.css';
import '../../css/u/u1ts3dbke.css';
import '../../css/z/z2w67ghwc.css';
import '../../css/k/kfztbhshm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGxUOMRb3d" x1="99.991%" x2=".01%" y1="-.011%" y2="100.01%"><stop offset=".344%" class="qea20536a"/><stop offset="46.89%" class="u1ts3dbke"/><stop offset="100%" class="z2w67ghwc"/></linearGradient></defs><path fill="url(#SVGxUOMRb3d)" class="kfztbhshm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kotlin" {...props}></Icon>
