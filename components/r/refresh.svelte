<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6mmidc7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g6mmidc7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:refresh" {...props}></Icon>
