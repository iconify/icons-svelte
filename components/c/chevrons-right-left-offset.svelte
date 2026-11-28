<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac3gkccvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac3gkccvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-right-left-offset" {...props}></Icon>
