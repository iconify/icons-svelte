<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pho01gbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pho01gbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-j-square-solid" {...props}></Icon>
