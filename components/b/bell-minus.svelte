<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_1x9gbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_1x9gbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bell-minus" {...props}></Icon>
