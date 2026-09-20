<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7n4f2bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7n4f2bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:number-6" {...props}></Icon>
