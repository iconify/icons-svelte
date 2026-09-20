<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw0w95kpx.css';
import '../../css/b/b1gwc0q-o.css';
import '../../css/y/ymyomxbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="rw0w95kpx"/><path class="b1gwc0q-o"/><path class="ymyomxbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:chart" {...props}></Icon>
