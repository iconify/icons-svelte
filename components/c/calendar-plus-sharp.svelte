<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpeeqbtjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpeeqbtjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-plus-sharp" {...props}></Icon>
