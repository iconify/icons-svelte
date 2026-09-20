<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok2vuvm6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ok2vuvm6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:robinhood" {...props}></Icon>
