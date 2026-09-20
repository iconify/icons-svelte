<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu4jkdj_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu4jkdj_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:minus-square3" {...props}></Icon>
