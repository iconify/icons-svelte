<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1kthrdrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1kthrdrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-down-3-filled" {...props}></Icon>
