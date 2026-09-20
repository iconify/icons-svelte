<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4q30tbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4q30tbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bug" {...props}></Icon>
