<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9nj1-bpg.css';
import '../../css/z/znrlbq9xw.css';
import '../../css/p/padkusb7b.css';
import '../../css/t/tlr6z7bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9nj1-bpg"/><path class="znrlbq9xw"/><path class="padkusb7b"/><path class="tlr6z7bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:chrome" {...props}></Icon>
