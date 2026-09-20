<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thhopss1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thhopss1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevrons-right-sharp-fill" {...props}></Icon>
