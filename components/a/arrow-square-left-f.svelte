<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju9jb6otc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ju9jb6otc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-square-left-f" {...props}></Icon>
