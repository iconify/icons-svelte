<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks-0vtbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks-0vtbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dholak-gloss" {...props}></Icon>
