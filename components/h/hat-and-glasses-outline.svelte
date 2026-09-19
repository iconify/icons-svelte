<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/ujarmf0ov.css';
import '../../css/y/ylhpf8tzr.css';
import '../../css/d/d4txopbsl.css';
import '../../css/y/ymjti08eb.css';
import '../../css/a/ahkl9uj7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="ujarmf0ov"/><path class="ylhpf8tzr"/><circle class="d4txopbsl"/><circle class="ymjti08eb"/><path class="ahkl9uj7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:hat-and-glasses-outline" {...props}></Icon>
