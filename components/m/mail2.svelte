<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvk4zyyjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tvk4zyyjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:mail2" {...props}></Icon>
