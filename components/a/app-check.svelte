<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzq7f1bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzq7f1bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-check" {...props}></Icon>
