<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za9qyur9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1280};
const content = `<path class="za9qyur9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrows-h" {...props}></Icon>
