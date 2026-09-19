<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6u7cmg7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6u7cmg7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:claude" {...props}></Icon>
