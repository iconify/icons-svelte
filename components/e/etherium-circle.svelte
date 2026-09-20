<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_k3e7ukx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_k3e7ukx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:etherium-circle" {...props}></Icon>
