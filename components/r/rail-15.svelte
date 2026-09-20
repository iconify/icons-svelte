<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl26hdf4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sl26hdf4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:rail-15" {...props}></Icon>
