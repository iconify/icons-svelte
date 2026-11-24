<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbn3egbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbn3egbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:eject-filled" {...props}></Icon>
