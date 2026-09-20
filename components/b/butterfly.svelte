<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy9p3gbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy9p3gbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:butterfly" {...props}></Icon>
