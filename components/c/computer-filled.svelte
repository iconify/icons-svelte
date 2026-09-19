<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f33j-7cos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b f33j-7cos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:computer-filled" {...props}></Icon>
