<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vepxg1bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vepxg1bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-fill" {...props}></Icon>
