<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhdunac-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhdunac-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pause-fill" {...props}></Icon>
