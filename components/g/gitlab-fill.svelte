<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqu-t3b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqu-t3b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gitlab-fill" {...props}></Icon>
