<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuc_41kpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fuc_41kpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-narrow-up" {...props}></Icon>
