<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a502a1b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-2};
const content = `<path class="a502a1b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:cogs" {...props}></Icon>
