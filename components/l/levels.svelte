<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9hx4balk.css';
import '../../css/g/gx74lwb0e.css';
import '../../css/b/b3v177x2s.css';
import '../../css/n/n0ij7acao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a9hx4balk"/><path class="gx74lwb0e"/><path class="b3v177x2s"/><path class="n0ij7acao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:levels" {...props}></Icon>
