<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqwusdbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqwusdbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dextf" {...props}></Icon>
