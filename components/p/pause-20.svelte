<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-02z6b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m-02z6b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pause-20" {...props}></Icon>
