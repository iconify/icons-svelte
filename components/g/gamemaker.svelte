<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ril_axbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ril_axbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gamemaker" {...props}></Icon>
