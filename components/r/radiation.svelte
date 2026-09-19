<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7w0gcror.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7w0gcror"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:radiation" {...props}></Icon>
