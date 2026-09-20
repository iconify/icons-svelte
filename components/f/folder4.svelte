<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp081n6cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp081n6cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder4" {...props}></Icon>
