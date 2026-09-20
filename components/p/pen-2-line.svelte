<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atf1isbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atf1isbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-2-line" {...props}></Icon>
