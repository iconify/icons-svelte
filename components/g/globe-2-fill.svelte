<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca6u321lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca6u321lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-2-fill" {...props}></Icon>
