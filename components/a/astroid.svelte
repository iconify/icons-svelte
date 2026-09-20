<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6u9v2bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6u9v2bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:astroid" {...props}></Icon>
