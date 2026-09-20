<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2s8njbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2s8njbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:body-shape-minimalistic-outline" {...props}></Icon>
