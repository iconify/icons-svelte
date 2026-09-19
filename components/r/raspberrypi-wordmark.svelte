<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbqbzqb3e.css';
import '../../css/g/gi8vxz4jo.css';
import '../../css/s/s2mrzdw6u.css';
import '../../css/u/us2wgibly.css';
import '../../css/k/k5qbcdbsg.css';
import '../../css/c/cqp-znbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xbqbzqb3e"/><path class="gi8vxz4jo"/><path class="s2mrzdw6u"/><path class="us2wgibly"/><path class="k5qbcdbsg"/><path class="cqp-znbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:raspberrypi-wordmark" {...props}></Icon>
