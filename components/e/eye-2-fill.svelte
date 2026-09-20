<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1yk7ac1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1yk7ac1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:eye-2-fill" {...props}></Icon>
