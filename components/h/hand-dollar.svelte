<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vctwy0bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vctwy0bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hand-dollar" {...props}></Icon>
