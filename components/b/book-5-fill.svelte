<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjf9-p5gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjf9-p5gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-5-fill" {...props}></Icon>
