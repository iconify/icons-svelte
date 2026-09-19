<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byawaojep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="byawaojep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:list-ol" {...props}></Icon>
