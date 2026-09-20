<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxxkm0vum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sxxkm0vum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:barrel" {...props}></Icon>
