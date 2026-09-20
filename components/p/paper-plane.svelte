<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cge0y-ejd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cge0y-ejd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:paper-plane" {...props}></Icon>
