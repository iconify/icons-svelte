<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4paecbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4paecbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:alarm-bell-ring-bold" {...props}></Icon>
