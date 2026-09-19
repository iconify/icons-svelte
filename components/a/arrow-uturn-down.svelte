<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za1v4_t6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="za1v4_t6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-uturn-down" {...props}></Icon>
