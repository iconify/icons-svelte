<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-xvne0je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-xvne0je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-g-diamond-solid" {...props}></Icon>
