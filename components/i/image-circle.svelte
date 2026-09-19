<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crens-u4t.css';
import '../../css/b/bwibdw4bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crens-u4t"/><path class="bwibdw4bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-circle" {...props}></Icon>
