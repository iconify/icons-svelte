<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w03r-d3lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w03r-d3lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:hash-solid" {...props}></Icon>
