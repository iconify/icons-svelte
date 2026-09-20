<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo4dh6bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo4dh6bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:briefcase-3-line" {...props}></Icon>
