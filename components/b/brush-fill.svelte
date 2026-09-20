<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsz7u7b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsz7u7b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brush-fill" {...props}></Icon>
