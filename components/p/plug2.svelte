<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzc3-d5gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzc3-d5gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:plug2" {...props}></Icon>
