<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izr1mgbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izr1mgbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:flash-allowed" {...props}></Icon>
