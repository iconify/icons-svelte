<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc-dftb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc-dftb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lintcode" {...props}></Icon>
