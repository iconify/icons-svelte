<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h16k0hb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h16k0hb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:lock-closed-20-solid" {...props}></Icon>
