<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-l86pv5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f-l86pv5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:refrigerator" {...props}></Icon>
