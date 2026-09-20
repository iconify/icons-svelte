<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_yhvzbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_yhvzbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kahoot" {...props}></Icon>
