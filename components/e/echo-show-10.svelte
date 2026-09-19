<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktpsno26x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktpsno26x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-show-10" {...props}></Icon>
