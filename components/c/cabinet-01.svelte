<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2lrwachb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2lrwachb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cabinet-01" {...props}></Icon>
