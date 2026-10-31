<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6iq38gjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6iq38gjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-6-round" {...props}></Icon>
