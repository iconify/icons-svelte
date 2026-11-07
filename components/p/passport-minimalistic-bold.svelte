<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqeyqsb0i.css';
import '../../css/n/nn7oqiafx.css';
import '../../css/v/vfk2nmbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqeyqsb0i"/><path class="nn7oqiafx"/><path clip-rule="evenodd" class="vfk2nmbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:passport-minimalistic-bold" {...props}></Icon>
