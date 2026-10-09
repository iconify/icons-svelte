<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzzrkrbqw.css';
import '../../css/y/ya12bvd4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uzzrkrbqw"/><path class="ya12bvd4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-open-20-bold" {...props}></Icon>
