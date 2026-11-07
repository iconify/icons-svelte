<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7zz7vboy.css';
import '../../css/i/ipogvcwzq.css';
import '../../css/n/nr35mg1ux.css';
import '../../css/i/i9yxaoc2b.css';
import '../../css/b/b1qrr3bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7zz7vboy"/><path class="ipogvcwzq"/><path class="nr35mg1ux"/><path class="i9yxaoc2b"/><path class="b1qrr3bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-play-bold-duotone" {...props}></Icon>
