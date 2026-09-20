<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgiw3fv-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgiw3fv-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rocky-linux" {...props}></Icon>
