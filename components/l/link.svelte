<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_h9hlbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-3};
const content = `<path class="c_h9hlbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:link" {...props}></Icon>
