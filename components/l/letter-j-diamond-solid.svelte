<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji-_atb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji-_atb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-j-diamond-solid" {...props}></Icon>
