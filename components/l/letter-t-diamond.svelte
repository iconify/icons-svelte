<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atboy2bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atboy2bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-t-diamond" {...props}></Icon>
