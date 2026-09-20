<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ongdct72a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ongdct72a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-text-fill" {...props}></Icon>
