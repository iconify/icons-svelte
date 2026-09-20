<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f533snb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f533snb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:inbox-down-solid" {...props}></Icon>
