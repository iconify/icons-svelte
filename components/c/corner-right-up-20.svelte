<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkc9nmf3a.css';
import '../../css/z/zosfd94fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gkc9nmf3a"/><path class="zosfd94fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-right-up-20" {...props}></Icon>
