<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co1p06nje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co1p06nje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:report-fill" {...props}></Icon>
