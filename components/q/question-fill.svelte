<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-j6szbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-j6szbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:question-fill" {...props}></Icon>
