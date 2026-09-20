<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qurobomoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qurobomoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:horn-2-fill" {...props}></Icon>
