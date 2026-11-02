<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecyrwhb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecyrwhb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clouds-line" {...props}></Icon>
