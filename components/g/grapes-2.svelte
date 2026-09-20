<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5tlv01gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t5tlv01gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:grapes-2" {...props}></Icon>
