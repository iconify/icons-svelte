<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgwl94b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgwl94b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:euro-solid" {...props}></Icon>
