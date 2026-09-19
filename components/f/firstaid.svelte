<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2f5krd8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o2f5krd8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:firstaid" {...props}></Icon>
