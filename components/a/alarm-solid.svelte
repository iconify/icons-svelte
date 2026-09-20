<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1mfc1b6e.css';
import '../../css/m/m9-ge182a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e1mfc1b6e"/><path clip-rule="evenodd" class="m9-ge182a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:alarm-solid" {...props}></Icon>
