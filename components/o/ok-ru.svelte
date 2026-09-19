<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkr3csbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkr3csbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:ok-ru" {...props}></Icon>
