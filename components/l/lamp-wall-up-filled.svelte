<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqdyx3lxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqdyx3lxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lamp-wall-up-filled" {...props}></Icon>
