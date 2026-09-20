<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vmfu1uq8n.css';
import '../../css/d/dguhd6bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vmfu1uq8n"/><circle transform="rotate(45 14.828 9.172)" class="dguhd6bfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:comet-line" {...props}></Icon>
