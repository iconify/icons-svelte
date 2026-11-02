<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zudpwdv0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zudpwdv0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ham-line" {...props}></Icon>
