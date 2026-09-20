<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6x2luhbf.css';
import '../../css/d/dnqhx8bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="w6x2luhbf"/><path class="dnqhx8bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:add-1m" {...props}></Icon>
