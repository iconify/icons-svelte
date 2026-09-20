<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1teaibpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1teaibpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:award-alt" {...props}></Icon>
