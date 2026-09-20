<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp41uubho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="jp41uubho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:messenger" {...props}></Icon>
