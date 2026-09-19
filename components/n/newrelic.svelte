<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo1fbbcra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lo1fbbcra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:newrelic" {...props}></Icon>
