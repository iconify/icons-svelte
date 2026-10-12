<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co2y78wts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co2y78wts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:parking-meter-filled" {...props}></Icon>
