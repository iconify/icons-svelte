<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yym0m6b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yym0m6b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chevron-down-up" {...props}></Icon>
