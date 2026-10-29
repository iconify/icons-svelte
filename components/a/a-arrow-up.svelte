<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5__2gsjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5__2gsjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:a-arrow-up" {...props}></Icon>
