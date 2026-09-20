<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc7pr0bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc7pr0bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-y-octagon-solid" {...props}></Icon>
