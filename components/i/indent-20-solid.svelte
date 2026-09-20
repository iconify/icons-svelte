<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_x3e4-7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b_x3e4-7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:indent-20-solid" {...props}></Icon>
