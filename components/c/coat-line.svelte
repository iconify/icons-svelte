<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chk0begud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chk0begud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coat-line" {...props}></Icon>
