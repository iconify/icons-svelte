<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkps0hbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkps0hbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-l-diamond-solid" {...props}></Icon>
