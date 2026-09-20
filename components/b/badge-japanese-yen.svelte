<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xop-chz3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xop-chz3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-japanese-yen" {...props}></Icon>
