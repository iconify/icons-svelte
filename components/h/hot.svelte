<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt3yji6_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gt3yji6_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:hot" {...props}></Icon>
