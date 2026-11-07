<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvymvrbay.css';
import '../../css/y/yu315fbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvymvrbay"/><path class="yu315fbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:logout-2-bold" {...props}></Icon>
