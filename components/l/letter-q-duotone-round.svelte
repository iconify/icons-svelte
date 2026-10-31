<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mylinobyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mylinobyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-q-duotone-round" {...props}></Icon>
