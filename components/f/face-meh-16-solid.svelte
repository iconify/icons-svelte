<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4qjz4jhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4qjz4jhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-meh-16-solid" {...props}></Icon>
