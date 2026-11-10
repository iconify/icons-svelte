<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6lx4hq4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n6lx4hq4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:camera-slash-20-solid" {...props}></Icon>
