<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-e6s_xyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-e6s_xyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:presentation-lines-alt" {...props}></Icon>
