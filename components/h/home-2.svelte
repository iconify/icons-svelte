<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3_mn_6bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3_mn_6bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:home-2" {...props}></Icon>
