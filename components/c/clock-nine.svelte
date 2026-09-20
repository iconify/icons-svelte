<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tubomzbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tubomzbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:clock-nine" {...props}></Icon>
