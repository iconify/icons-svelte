<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3jke53fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y3jke53fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:attraction-15" {...props}></Icon>
