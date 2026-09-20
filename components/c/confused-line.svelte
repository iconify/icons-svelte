<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff1o3km4s.css';
import '../../css/s/s3ykwebuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff1o3km4s"/><path class="s3ykwebuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:confused-line" {...props}></Icon>
