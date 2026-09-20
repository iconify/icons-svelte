<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe6jk7bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe6jk7bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:enter-door-fill" {...props}></Icon>
