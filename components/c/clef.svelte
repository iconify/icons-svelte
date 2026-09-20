<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvlytjb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvlytjb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clef" {...props}></Icon>
