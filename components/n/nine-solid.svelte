<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-nfdt3vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-nfdt3vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:nine-solid" {...props}></Icon>
