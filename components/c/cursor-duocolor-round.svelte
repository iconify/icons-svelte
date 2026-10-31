<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlp85eb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlp85eb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cursor-duocolor-round" {...props}></Icon>
