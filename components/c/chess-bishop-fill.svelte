<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqxr__w0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqxr__w0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chess-bishop-fill" {...props}></Icon>
