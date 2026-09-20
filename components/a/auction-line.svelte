<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnv13yfyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnv13yfyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:auction-line" {...props}></Icon>
