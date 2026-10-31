<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmycexbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmycexbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pill-bottle-gloss" {...props}></Icon>
