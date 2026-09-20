<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmx5yk91i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmx5yk91i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:moon-light" {...props}></Icon>
