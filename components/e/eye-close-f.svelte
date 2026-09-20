<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0ysl7lyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="b0ysl7lyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:eye-close-f" {...props}></Icon>
