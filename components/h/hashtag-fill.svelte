<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8sstsy7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8sstsy7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hashtag-fill" {...props}></Icon>
