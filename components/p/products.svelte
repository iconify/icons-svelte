<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i69c5cblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i69c5cblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:products" {...props}></Icon>
