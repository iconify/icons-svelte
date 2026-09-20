<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgd2dpqcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgd2dpqcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pizza" {...props}></Icon>
