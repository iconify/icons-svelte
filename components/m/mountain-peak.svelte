<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztzh1dyat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztzh1dyat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mountain-peak" {...props}></Icon>
