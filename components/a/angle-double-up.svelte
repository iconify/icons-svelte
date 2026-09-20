<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtt7l7bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtt7l7bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:angle-double-up" {...props}></Icon>
