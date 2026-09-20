<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmylpfk6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmylpfk6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-h" {...props}></Icon>
