<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xco31rbaj.css';
import '../../css/f/f_0-3nbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xco31rbaj"/><path class="f_0-3nbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:house-filled" {...props}></Icon>
