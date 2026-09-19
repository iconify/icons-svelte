<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7shhm5zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q7shhm5zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:check-badge-20-solid" {...props}></Icon>
