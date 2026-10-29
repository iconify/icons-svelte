<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vm23nj9rp.css';
import '../../css/m/m2bzfy6-u.css';
import '../../css/g/g5qr6-bxa.css';
import '../../css/m/m0dzyqufg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vm23nj9rp wm-k"/><path class="m2bzfy6-u wm-a"/><path class="g5qr6-bxa wm-k"/><path class="m0dzyqufg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cactus-sketch" {...props}></Icon>
