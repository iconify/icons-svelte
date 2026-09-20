<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9skzweqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9skzweqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candy-2-fill" {...props}></Icon>
