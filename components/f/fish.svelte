<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq0y6rv0t.css';
import '../../css/j/ju6ln2bjw.css';
import '../../css/s/sah522b5e.css';
import '../../css/k/krkjhqbxc.css';
import '../../css/q/qr7g99buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vq0y6rv0t"/><path class="ju6ln2bjw"/><path class="sah522b5e"/><path class="krkjhqbxc"/><path class="qr7g99buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:fish" {...props}></Icon>
