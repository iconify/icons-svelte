<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrq5u1bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrq5u1bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:radical" {...props}></Icon>
