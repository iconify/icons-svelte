<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inkw-bc-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inkw-bc-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bereal" {...props}></Icon>
