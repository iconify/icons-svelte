<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r49rvebmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r49rvebmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:messages-square-fill" {...props}></Icon>
