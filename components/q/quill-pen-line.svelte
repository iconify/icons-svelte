<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx8t_pbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx8t_pbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quill-pen-line" {...props}></Icon>
