<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bundg05xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bundg05xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:oil-fill" {...props}></Icon>
