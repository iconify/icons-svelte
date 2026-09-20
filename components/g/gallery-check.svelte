<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja7ltjp0f.css';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/btlxfkbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGeEBWIcGE" class="ja7ltjp0f"/></defs><g clip-rule="evenodd" class="n1lsf0bnc"><path class="btlxfkbwh"/><use href="#SVGeEBWIcGE"/><use href="#SVGeEBWIcGE"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gallery-check" {...props}></Icon>
