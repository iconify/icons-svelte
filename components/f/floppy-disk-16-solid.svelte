<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qncigyyhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qncigyyhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:floppy-disk-16-solid" {...props}></Icon>
