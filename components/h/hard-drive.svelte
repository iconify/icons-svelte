<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhpnjlb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qhpnjlb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hard-drive" {...props}></Icon>
