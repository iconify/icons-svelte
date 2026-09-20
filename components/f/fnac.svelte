<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja4yemf_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja4yemf_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fnac" {...props}></Icon>
