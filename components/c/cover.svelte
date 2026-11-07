<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/e3z8dsbjk.css';
import '../../css/q/q26lahbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="e3z8dsbjk"/><path class="q26lahbif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:cover" {...props}></Icon>
