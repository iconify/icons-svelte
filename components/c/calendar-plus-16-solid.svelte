<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk0o3qbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zk0o3qbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-plus-16-solid" {...props}></Icon>
