<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jih5fdbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jih5fdbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:archive" {...props}></Icon>
