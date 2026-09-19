<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlg7xccoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlg7xccoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:rain" {...props}></Icon>
