<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9uaj7byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9uaj7byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:case-sensitive" {...props}></Icon>
