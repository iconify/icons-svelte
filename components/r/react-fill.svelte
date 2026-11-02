<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebqscw0ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebqscw0ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:react-fill" {...props}></Icon>
