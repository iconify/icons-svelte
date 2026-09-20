<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9_he8bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9_he8bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-down-s" {...props}></Icon>
