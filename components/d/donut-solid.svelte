<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6smo0bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6smo0bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:donut-solid" {...props}></Icon>
