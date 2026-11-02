<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzd2uob7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzd2uob7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-up-2-fill" {...props}></Icon>
