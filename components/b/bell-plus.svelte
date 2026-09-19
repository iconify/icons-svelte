<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm9d15bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm9d15bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bell-plus" {...props}></Icon>
