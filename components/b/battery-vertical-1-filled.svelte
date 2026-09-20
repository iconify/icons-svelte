<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj4qumg9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj4qumg9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-vertical-1-filled" {...props}></Icon>
