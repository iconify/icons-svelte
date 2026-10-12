<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os3wfcb2g.css';
import '../../css/d/duhv4jbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="os3wfcb2g"/><path class="duhv4jbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cat-20" {...props}></Icon>
