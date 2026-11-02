<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-d8ncw7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-d8ncw7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chevrons-down-up-line" {...props}></Icon>
