<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/matj_mbse.css';
import '../../css/s/su639bbye.css';
import '../../css/f/f498sebzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="matj_mbse"/><path class="su639bbye"/><path class="f498sebzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:configuration-management" {...props}></Icon>
