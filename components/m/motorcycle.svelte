<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ame5gh01i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1280};
const content = `<path class="ame5gh01i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:motorcycle" {...props}></Icon>
