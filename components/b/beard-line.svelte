<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvesrfbzk.css';
import '../../css/u/ur907-bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvesrfbzk"/><path class="ur907-bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:beard-line" {...props}></Icon>
