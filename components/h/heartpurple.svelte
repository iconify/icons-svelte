<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzjgi_bqf.css';
import '../../css/d/dx1vlmbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzjgi_bqf"/><path class="dx1vlmbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heartpurple" {...props}></Icon>
