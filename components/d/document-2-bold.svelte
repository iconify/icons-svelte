<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd-1mab0x.css';
import '../../css/u/uypdg1btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vd-1mab0x"/><path class="uypdg1btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-2-bold" {...props}></Icon>
