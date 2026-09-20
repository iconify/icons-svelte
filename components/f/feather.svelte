<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idgt6wb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idgt6wb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:feather" {...props}></Icon>
