<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztdaajb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ztdaajb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:helmet" {...props}></Icon>
