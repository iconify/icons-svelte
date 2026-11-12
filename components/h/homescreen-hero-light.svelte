<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imvewngax.css';
import '../../css/h/hexr8-bsz.css';
import '../../css/n/nadauofsf.css';
import '../../css/y/y--w-mb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="imvewngax"/><path class="hexr8-bsz"/><path class="nadauofsf"/><path class="y--w-mb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homescreen-hero-light" {...props}></Icon>
