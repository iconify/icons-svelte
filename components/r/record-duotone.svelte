<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qucn7nbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qucn7nbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:record-duotone" {...props}></Icon>
