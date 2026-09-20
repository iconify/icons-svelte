<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4z7izb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n4z7izb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bicycle-15" {...props}></Icon>
