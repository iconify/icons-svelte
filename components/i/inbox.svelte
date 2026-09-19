<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghn1gb57e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ghn1gb57e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:inbox" {...props}></Icon>
