<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_52uqbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b_52uqbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:aries" {...props}></Icon>
