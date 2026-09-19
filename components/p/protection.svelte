<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/c/ca3oflbdp.css';
import '../../css/g/gx8mphfqp.css';
import '../../css/f/fa3pa8bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="ca3oflbdp"/><path class="gx8mphfqp"/><path class="fa3pa8bch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:protection" {...props}></Icon>
