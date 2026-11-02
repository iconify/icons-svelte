<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yud24mw5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yud24mw5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hiking-fill" {...props}></Icon>
