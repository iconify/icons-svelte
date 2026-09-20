<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb0t-15qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lb0t-15qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dot" {...props}></Icon>
