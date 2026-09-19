<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg-wgrjyj.css';
import '../../css/l/lmzdaxwoj.css';
import '../../css/n/nd2aiyu9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="yg-wgrjyj"><path class="lmzdaxwoj"/><path class="nd2aiyu9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:gas-tank-drop" {...props}></Icon>
