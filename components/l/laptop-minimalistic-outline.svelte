<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr9kmlbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vr9kmlbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-minimalistic-outline" {...props}></Icon>
