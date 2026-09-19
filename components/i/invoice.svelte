<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e64surbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1024};
const content = `<path class="e64surbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:invoice" {...props}></Icon>
