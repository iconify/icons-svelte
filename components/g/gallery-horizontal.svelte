<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mwfiol2dj.css';
import '../../css/a/auvfzibbj.css';
import '../../css/z/zs3id2b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mwfiol2dj"/><rect class="auvfzibbj"/><path class="zs3id2b8k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:gallery-horizontal" {...props}></Icon>
