<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uskg7un7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uskg7un7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mouse-right" {...props}></Icon>
