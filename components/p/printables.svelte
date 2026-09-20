<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy1asibtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy1asibtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:printables" {...props}></Icon>
