<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e957222re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e957222re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:down-triangle" {...props}></Icon>
