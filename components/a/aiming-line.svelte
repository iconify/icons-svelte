<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izoqmjb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izoqmjb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aiming-line" {...props}></Icon>
