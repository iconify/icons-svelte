<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi4vo2skc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi4vo2skc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-from-line-fill-round" {...props}></Icon>
