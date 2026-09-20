<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnjfgabty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnjfgabty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:arrow-up-large-2" {...props}></Icon>
