<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j88of6b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j88of6b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kontoj-light" {...props}></Icon>
