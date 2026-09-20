<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byxhw9b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="byxhw9b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:notification-application-1-remix" {...props}></Icon>
