<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqh_vbctn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqh_vbctn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:layout-panel-bottom" {...props}></Icon>
