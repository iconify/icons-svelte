<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uueukmy4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uueukmy4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:modx" {...props}></Icon>
