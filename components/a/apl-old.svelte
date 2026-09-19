<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7t3zob6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":575,"height":512};
const content = `<path class="m7t3zob6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:apl-old" {...props}></Icon>
