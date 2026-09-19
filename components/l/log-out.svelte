<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2-0v_biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2-0v_biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:log-out" {...props}></Icon>
