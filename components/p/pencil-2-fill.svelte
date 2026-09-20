<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aib1ujbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aib1ujbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-2-fill" {...props}></Icon>
