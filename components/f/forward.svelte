<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb78fs52v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb78fs52v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:forward" {...props}></Icon>
