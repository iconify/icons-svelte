<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfn1or_0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfn1or_0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:proper-subset" {...props}></Icon>
