<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ps9nbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ps9nbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ear-gloss" {...props}></Icon>
