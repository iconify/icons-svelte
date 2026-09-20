<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a18-ftbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a18-ftbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:air-balloon-fill" {...props}></Icon>
