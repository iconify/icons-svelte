<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezwqmabwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezwqmabwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:caret-down-outline" {...props}></Icon>
