<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ua0mm9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="e7ua0mm9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:calendar-plus-solid" {...props}></Icon>
