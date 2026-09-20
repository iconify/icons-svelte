<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xju_mz_ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xju_mz_ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:progate" {...props}></Icon>
