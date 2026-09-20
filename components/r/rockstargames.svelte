<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gikr6zbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gikr6zbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rockstargames" {...props}></Icon>
