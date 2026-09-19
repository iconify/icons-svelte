<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df4b_9t3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="df4b_9t3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bottomborder" {...props}></Icon>
