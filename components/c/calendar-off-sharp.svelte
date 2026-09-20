<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uht88ogek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uht88ogek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-off-sharp" {...props}></Icon>
