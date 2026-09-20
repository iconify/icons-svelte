<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/homf0vbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="homf0vbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:facebook" {...props}></Icon>
