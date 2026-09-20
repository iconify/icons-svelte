<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iouj3fbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iouj3fbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:box-fill" {...props}></Icon>
