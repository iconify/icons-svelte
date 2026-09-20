<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiu4-0byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="yiu4-0byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:anchor-solid" {...props}></Icon>
