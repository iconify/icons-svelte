<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmnue0ahf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmnue0ahf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chield-fill" {...props}></Icon>
