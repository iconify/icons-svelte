<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj6k4bkhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj6k4bkhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:notification-outline" {...props}></Icon>
