<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f0-uvxvpa.css';
import '../../css/c/cb211lb7c.css';
import '../../css/n/n3b-5s0yy.css';
import '../../css/b/b0b1n7bzo.css';
import '../../css/q/qwh48ubyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f0-uvxvpa"/><path class="cb211lb7c wm-k"/><path class="n3b-5s0yy wm-a"/><path class="b0b1n7bzo wm-k"/><path class="qwh48ubyu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mountain-sketch" {...props}></Icon>
