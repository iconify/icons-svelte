<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnqof6pva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fnqof6pva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chevron-right-small" {...props}></Icon>
