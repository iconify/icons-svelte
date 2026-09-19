<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbo-9nggs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bbo-9nggs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:gravefour" {...props}></Icon>
