<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_txabqkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u_txabqkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-bold" {...props}></Icon>
