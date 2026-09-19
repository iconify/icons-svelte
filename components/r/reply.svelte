<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx5bmgb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx5bmgb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:reply" {...props}></Icon>
