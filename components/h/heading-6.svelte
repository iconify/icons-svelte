<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3kyahcdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3kyahcdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-6" {...props}></Icon>
