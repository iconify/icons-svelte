<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcgi2ob_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcgi2ob_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:osmc" {...props}></Icon>
