<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u36f9db9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u36f9db9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dogecoin-doge-fill" {...props}></Icon>
