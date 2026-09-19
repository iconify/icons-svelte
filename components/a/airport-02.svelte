<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqmv7ubar.css';
import '../../css/s/svdy80z7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fqmv7ubar"/><path class="svdy80z7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:airport-02" {...props}></Icon>
