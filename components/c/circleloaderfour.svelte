<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud46_zbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="ud46_zbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleloaderfour" {...props}></Icon>
