<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihmh29bqx.css';
import '../../css/l/lhghp8bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ihmh29bqx"/><path clip-rule="evenodd" class="lhghp8bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calendar-date-range-16-solid" {...props}></Icon>
