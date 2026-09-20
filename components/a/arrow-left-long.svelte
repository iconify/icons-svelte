<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ibyacxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="l-ibyacxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-left-long" {...props}></Icon>
