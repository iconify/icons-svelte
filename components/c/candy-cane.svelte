<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg69lwbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg69lwbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:candy-cane" {...props}></Icon>
