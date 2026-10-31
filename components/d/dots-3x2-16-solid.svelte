<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqvapdwkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wqvapdwkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x2-16-solid" {...props}></Icon>
