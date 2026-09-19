<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvsvn_42u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":650,"height":750};
const content = `<path class="yvsvn_42u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:menu" {...props}></Icon>
