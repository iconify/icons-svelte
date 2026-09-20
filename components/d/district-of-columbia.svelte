<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw-m6vb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yw-m6vb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:district-of-columbia" {...props}></Icon>
