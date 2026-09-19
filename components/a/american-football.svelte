<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w3f0rzbgw.css';
import '../../css/d/d7iqucb8k.css';
import '../../css/r/r7ldvdbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="w3f0rzbgw"/><path class="d7iqucb8k"/><path class="r7ldvdbgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:american-football" {...props}></Icon>
