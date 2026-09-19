<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar3ql4bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar3ql4bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:arrow-up" {...props}></Icon>
