<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts6m84bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ts6m84bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:oil-fill" {...props}></Icon>
