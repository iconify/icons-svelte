<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4v56n5fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4v56n5fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-2-line" {...props}></Icon>
