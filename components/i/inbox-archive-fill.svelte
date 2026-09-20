<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa7-4xb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa7-4xb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:inbox-archive-fill" {...props}></Icon>
