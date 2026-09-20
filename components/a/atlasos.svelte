<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbq16f0me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbq16f0me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:atlasos" {...props}></Icon>
