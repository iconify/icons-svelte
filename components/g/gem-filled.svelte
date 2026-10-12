<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyue1vbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyue1vbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gem-filled" {...props}></Icon>
