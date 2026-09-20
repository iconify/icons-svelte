<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7v9cf4ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7v9cf4ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:eye-opened-light" {...props}></Icon>
