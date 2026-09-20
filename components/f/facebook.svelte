<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1k1bkb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1k1bkb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:facebook" {...props}></Icon>
