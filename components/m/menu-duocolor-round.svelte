<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7ocnpxex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7ocnpxex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-duocolor-round" {...props}></Icon>
