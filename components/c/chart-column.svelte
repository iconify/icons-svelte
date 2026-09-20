<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3b0k7owk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3b0k7owk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-column" {...props}></Icon>
