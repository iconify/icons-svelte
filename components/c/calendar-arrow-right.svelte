<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc2v8ab1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc2v8ab1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-arrow-right" {...props}></Icon>
