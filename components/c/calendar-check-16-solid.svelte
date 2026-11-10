<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsrof7c5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zsrof7c5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-check-16-solid" {...props}></Icon>
