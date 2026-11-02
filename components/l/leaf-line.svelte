<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbwvw97ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbwvw97ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leaf-line" {...props}></Icon>
