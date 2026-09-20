<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai5h96bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai5h96bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arow-to-right-fill" {...props}></Icon>
