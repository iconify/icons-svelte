<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quqt_-b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quqt_-b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:quote-up-filled" {...props}></Icon>
