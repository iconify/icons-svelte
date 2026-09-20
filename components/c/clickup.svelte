<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqn6k6b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqn6k6b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:clickup" {...props}></Icon>
