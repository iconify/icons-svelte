<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak0owtb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ak0owtb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:mic-circle-f" {...props}></Icon>
