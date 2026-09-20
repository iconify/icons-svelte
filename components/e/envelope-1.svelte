<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ies6qcc_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ies6qcc_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:envelope-1" {...props}></Icon>
