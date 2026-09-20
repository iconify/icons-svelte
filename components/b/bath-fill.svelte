<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyzx15osk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyzx15osk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bath-fill" {...props}></Icon>
