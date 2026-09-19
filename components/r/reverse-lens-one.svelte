<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/tmngr6b0v.css';
import '../../css/j/jn2jlqbfe.css';
import '../../css/n/n0rx2i3tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="tmngr6b0v"/><path class="jn2jlqbfe"/><path class="n0rx2i3tg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:reverse-lens-one" {...props}></Icon>
