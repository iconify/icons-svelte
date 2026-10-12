<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtkdzbbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtkdzbbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dam-filled" {...props}></Icon>
