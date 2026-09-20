<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp2l6s40o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp2l6s40o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-y-square" {...props}></Icon>
