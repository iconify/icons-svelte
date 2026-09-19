<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vai2b4bfw.css';
import '../../css/s/s4lttrqws.css';
import '../../css/w/wzn6zhbvq.css';
import '../../css/t/tu54racff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vai2b4bfw"/><g class="s4lttrqws"><path class="wzn6zhbvq"/><path class="tu54racff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:lua-server" {...props}></Icon>
