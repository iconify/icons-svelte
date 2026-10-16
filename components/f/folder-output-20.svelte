<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwb0facpd.css';
import '../../css/x/x5goyhbiu.css';
import '../../css/t/tqvccub8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xwb0facpd"/><path class="x5goyhbiu"/><path class="tqvccub8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-output-20" {...props}></Icon>
