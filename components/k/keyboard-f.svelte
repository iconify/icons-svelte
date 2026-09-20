<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_q6c7r9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="g_q6c7r9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:keyboard-f" {...props}></Icon>
