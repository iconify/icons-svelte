<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn42al5mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="bn42al5mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-square-up-right-f" {...props}></Icon>
