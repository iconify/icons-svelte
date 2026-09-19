<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l20n-1ngj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l20n-1ngj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:gift-top" {...props}></Icon>
