<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw9-pfc_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hw9-pfc_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bottom-left-solid" {...props}></Icon>
