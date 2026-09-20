<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdu58zbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdu58zbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-kid-filled" {...props}></Icon>
