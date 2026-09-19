<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt9f3ub2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gt9f3ub2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:map-pin" {...props}></Icon>
