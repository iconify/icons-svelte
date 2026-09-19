<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhbk6obna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yhbk6obna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:magnet" {...props}></Icon>
