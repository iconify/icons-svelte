<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr102vbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jr102vbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:lettered-list-16-solid" {...props}></Icon>
