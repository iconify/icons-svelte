<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv62hbcmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv62hbcmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-vert-line" {...props}></Icon>
