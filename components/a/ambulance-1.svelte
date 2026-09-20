<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6l40s97s.css';
import '../../css/l/l08ti_b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6l40s97s"/><path clip-rule="evenodd" class="l08ti_b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ambulance-1" {...props}></Icon>
