<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn-w9f_5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn-w9f_5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:factory-2-fill" {...props}></Icon>
