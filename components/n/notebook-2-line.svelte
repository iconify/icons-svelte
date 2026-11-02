<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_72bhbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_72bhbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notebook-2-line" {...props}></Icon>
