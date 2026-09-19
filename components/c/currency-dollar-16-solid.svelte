<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bocfkcb9c.css';
import '../../css/p/pi8mxsaiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bocfkcb9c"/><path clip-rule="evenodd" class="pi8mxsaiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-dollar-16-solid" {...props}></Icon>
