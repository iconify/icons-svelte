<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcta-bc5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcta-bc5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aiming-fill" {...props}></Icon>
