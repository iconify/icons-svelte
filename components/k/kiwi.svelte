<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-m70vbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":832};
const content = `<path class="c-m70vbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:kiwi" {...props}></Icon>
