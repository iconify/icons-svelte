<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn4b8bcbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn4b8bcbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:air-condition-line" {...props}></Icon>
