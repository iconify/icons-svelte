<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sypwx4bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sypwx4bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:line" {...props}></Icon>
