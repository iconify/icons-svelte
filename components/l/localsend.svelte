<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxi0iukvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxi0iukvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:localsend" {...props}></Icon>
