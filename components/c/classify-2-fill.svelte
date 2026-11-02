<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr7ozebwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr7ozebwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-2-fill" {...props}></Icon>
