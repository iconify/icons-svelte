<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8_4imbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8_4imbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-up-fill" {...props}></Icon>
