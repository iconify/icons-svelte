<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biuqp6b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biuqp6b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notification-off-fill" {...props}></Icon>
