<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jvzm0ac7t.css';
import '../../css/i/iwt0w8b9p.css';
import '../../css/u/u3tqh8b-y.css';
import '../../css/p/p2spj-b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jvzm0ac7t"/><path class="iwt0w8b9p"/><path class="u3tqh8b-y"/><path class="p2spj-b_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quit-full-screen-linear" {...props}></Icon>
