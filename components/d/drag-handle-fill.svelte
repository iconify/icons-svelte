<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzogmsbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzogmsbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:drag-handle-fill" {...props}></Icon>
