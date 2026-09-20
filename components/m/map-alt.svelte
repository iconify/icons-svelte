<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbqk0lyvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbqk0lyvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map-alt" {...props}></Icon>
