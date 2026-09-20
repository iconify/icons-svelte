<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt83wcb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt83wcb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:minus-solid" {...props}></Icon>
