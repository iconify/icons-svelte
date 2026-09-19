<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kon2j4bpd.css';
import '../../css/m/mjknonirp.css';
import '../../css/l/lmf0ecbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="kon2j4bpd"/><path class="mjknonirp"/><circle class="lmf0ecbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:media-changer-outline-badged" {...props}></Icon>
