<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upqsv0b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="upqsv0b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:flag-outline" {...props}></Icon>
