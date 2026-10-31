<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny-96bjvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ny-96bjvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist-16-solid" {...props}></Icon>
