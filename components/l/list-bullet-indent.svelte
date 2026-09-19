<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az_vxbc1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="az_vxbc1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:list-bullet-indent" {...props}></Icon>
