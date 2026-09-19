<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghk0ryb3g.css';
import '../../css/f/f-em3h96r.css';
import '../../css/f/fjfsszbfp.css';
import '../../css/i/i050vtjae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ghk0ryb3g"/><path class="f-em3h96r"/><path class="fjfsszbfp"/><path class="i050vtjae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-construct" {...props}></Icon>
