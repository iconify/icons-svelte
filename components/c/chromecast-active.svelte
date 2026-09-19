<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u665ban.css';
import '../../css/c/c5-cmyb3j.css';
import '../../css/u/ugzu9rb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="c5-cmyb3j"/><path clip-rule="evenodd" class="ugzu9rb9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chromecast-active" {...props}></Icon>
