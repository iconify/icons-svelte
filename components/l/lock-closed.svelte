<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtlog_bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtlog_bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:lock-closed" {...props}></Icon>
