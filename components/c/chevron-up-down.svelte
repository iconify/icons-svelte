<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsxz30s9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fsxz30s9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chevron-up-down" {...props}></Icon>
