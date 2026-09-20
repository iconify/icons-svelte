<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v30e-s2jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v30e-s2jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-2-fill" {...props}></Icon>
