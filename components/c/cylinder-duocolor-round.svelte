<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mun92rbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mun92rbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cylinder-duocolor-round" {...props}></Icon>
