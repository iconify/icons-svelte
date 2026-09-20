<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx3_iti8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx3_iti8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:midi-fill" {...props}></Icon>
