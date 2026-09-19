<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilsrssbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":698};
const content = `<path class="ilsrssbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:laugh" {...props}></Icon>
