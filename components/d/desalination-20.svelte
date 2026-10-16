<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gah9kwbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gah9kwbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desalination-20" {...props}></Icon>
