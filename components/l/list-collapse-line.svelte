<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abdmc1bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abdmc1bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-collapse-line" {...props}></Icon>
