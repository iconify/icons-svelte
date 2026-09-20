<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4avzjb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4avzjb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pentagon-fill" {...props}></Icon>
