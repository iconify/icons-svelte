<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bske83x9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bske83x9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:outbox" {...props}></Icon>
