<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/ny87dobof.css';
import '../../css/g/gtc2uzbxu.css';
import '../../css/d/d8wygibdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ny87dobof"/><circle class="gtc2uzbxu"/><path class="d8wygibdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:chameleon" {...props}></Icon>
