<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppprx6why.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-4.5};
const content = `<path class="ppprx6why"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-up" {...props}></Icon>
