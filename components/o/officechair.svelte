<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-j6hab_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="d-j6hab_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:officechair" {...props}></Icon>
