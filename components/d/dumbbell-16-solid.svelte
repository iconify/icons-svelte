<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6huge5ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w6huge5ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dumbbell-16-solid" {...props}></Icon>
