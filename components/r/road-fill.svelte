<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owt8m26yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owt8m26yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:road-fill" {...props}></Icon>
