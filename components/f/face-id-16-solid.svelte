<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8defhbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l8defhbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-id-16-solid" {...props}></Icon>
