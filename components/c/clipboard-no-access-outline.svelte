<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq5r37b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rq5r37b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clipboard-no-access-outline" {...props}></Icon>
