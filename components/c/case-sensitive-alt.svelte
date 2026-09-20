<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxgv3ovom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxgv3ovom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:case-sensitive-alt" {...props}></Icon>
