<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahgmc5vep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahgmc5vep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-3-round" {...props}></Icon>
