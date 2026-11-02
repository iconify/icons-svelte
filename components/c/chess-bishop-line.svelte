<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic4q36b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic4q36b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chess-bishop-line" {...props}></Icon>
