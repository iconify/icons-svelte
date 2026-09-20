<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im2qk3bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im2qk3bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:feather" {...props}></Icon>
