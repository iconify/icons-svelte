<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5qs4zbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b5qs4zbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:plus-20-solid" {...props}></Icon>
