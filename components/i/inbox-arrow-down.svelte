<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6rk1e3su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6rk1e3su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:inbox-arrow-down" {...props}></Icon>
