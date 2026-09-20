<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/ol3qevala.css';
import '../../css/q/qlbh4ybeo.css';
import '../../css/k/kl16iub3v.css';
import '../../css/w/wvla7xgat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ol3qevala"/><path class="qlbh4ybeo"/><path class="kl16iub3v"/><path class="wvla7xgat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:app-window-search-text" {...props}></Icon>
