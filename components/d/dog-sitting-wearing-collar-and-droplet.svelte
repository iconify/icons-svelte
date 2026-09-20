<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv_jfuboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kv_jfuboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-wearing-collar-and-droplet" {...props}></Icon>
