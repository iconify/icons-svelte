<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go9nm4qyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go9nm4qyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:between-horizontal-start-line" {...props}></Icon>
