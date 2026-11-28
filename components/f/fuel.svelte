<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfht2wbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfht2wbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fuel" {...props}></Icon>
