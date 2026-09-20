<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyqv2ybri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyqv2ybri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:lock-hierarchy-bold" {...props}></Icon>
