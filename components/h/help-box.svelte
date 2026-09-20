<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn8ovob2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn8ovob2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:help-box" {...props}></Icon>
