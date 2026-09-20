<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zid-e6bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zid-e6bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cnfi" {...props}></Icon>
