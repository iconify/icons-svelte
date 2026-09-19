<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/k/kgoe69b6c.css';
import '../../css/i/iu5_1fbyz.css';
import '../../css/e/enlxepbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="kgoe69b6c"/><circle class="iu5_1fbyz"/><circle class="enlxepbgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:ellipsis-outline" {...props}></Icon>
