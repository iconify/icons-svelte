<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4gm5vbqz.css';
import '../../css/j/jw4xvqyjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4gm5vbqz"/><path class="jw4xvqyjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-security-fill" {...props}></Icon>
