<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx5qw-f6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx5qw-f6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:bell-off" {...props}></Icon>
