<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvl1kv60i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvl1kv60i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:quote-right" {...props}></Icon>
