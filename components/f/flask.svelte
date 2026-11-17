<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fzh5g6b7d.css';
import '../../css/y/ynhs8qbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fzh5g6b7d"/><path class="ynhs8qbaa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:flask" {...props}></Icon>
