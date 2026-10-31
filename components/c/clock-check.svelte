<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/k/k917d4bou.css';
import '../../css/y/yddab4ber.css';
import '../../css/p/p7ct5pm2p.css';
import '../../css/e/eywhs0bnc.css';
import '../../css/o/o9p1zzt3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="k917d4bou wm-shadow"/><path class="wm-shadow yddab4ber"/><path class="p7ct5pm2p"/><path class="eywhs0bnc"/><path class="o9p1zzt3p wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:clock-check" {...props}></Icon>
