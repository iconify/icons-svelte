<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzzkxlb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzzkxlb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-4-sharp-fill" {...props}></Icon>
