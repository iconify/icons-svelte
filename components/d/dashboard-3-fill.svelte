<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjwvxny-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjwvxny-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dashboard-3-fill" {...props}></Icon>
