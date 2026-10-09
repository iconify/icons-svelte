<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0zh2bb8f.css';
import '../../css/t/tnm3gqoro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s0zh2bb8f"/><path class="tnm3gqoro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:files-20" {...props}></Icon>
