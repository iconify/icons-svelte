<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1ta7ccsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1ta7ccsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:phone-off-outline" {...props}></Icon>
