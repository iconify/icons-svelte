<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4w2kqawh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="n4w2kqawh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:down-circle" {...props}></Icon>
