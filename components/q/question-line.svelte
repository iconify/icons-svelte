<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvxexubbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvxexubbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:question-line" {...props}></Icon>
