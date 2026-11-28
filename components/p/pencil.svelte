<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sttrdl2yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sttrdl2yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pencil" {...props}></Icon>
