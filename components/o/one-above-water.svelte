<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptah8jequ.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ptah8jequ"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:one-above-water" {...props}></Icon>
