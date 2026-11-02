<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiwy10b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiwy10b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pot-line" {...props}></Icon>
