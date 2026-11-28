<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7bqt9btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7bqt9btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-lock" {...props}></Icon>
