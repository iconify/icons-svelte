<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh2ya3bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh2ya3bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lock-solid" {...props}></Icon>
