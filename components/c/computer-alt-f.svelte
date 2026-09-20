<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozb5jvb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="ozb5jvb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:computer-alt-f" {...props}></Icon>
