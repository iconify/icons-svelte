<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3k9861yd.css';
import '../../css/s/sizcdbmji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3k9861yd"/><path class="sizcdbmji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bell-check" {...props}></Icon>
