<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhi_abczy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhi_abczy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:boom-box" {...props}></Icon>
