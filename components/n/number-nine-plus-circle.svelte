<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee10w_8jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee10w_8jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-nine-plus-circle" {...props}></Icon>
