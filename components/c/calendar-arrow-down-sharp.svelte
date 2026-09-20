<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4bney4jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4bney4jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-arrow-down-sharp" {...props}></Icon>
