<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoydhk-ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoydhk-ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:database-alert" {...props}></Icon>
