<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr8ptachn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr8ptachn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-horizontal-distribute-center-filled" {...props}></Icon>
