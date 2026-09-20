<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiygh8btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiygh8btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:probot" {...props}></Icon>
