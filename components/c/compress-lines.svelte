<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr8ituh-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr8ituh-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:compress-lines" {...props}></Icon>
