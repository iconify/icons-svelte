<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf9yt7bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf9yt7bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-right-double" {...props}></Icon>
