<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh5iqbbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh5iqbbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:admin-fill" {...props}></Icon>
