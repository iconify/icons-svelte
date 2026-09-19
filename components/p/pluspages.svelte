<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5jhruhbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e5jhruhbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pluspages" {...props}></Icon>
