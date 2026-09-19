<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wldyddchs.css';
import '../../css/d/d1ny50d5n.css';
import '../../css/e/ediclqbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="wldyddchs"><path class="d1ny50d5n"/><path class="ediclqbms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:map-of-japan" {...props}></Icon>
