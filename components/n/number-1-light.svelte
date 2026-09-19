<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrg-zm8yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrg-zm8yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-1-light" {...props}></Icon>
