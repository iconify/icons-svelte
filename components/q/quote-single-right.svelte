<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at9wev70d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at9wev70d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-single-right" {...props}></Icon>
