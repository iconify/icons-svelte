<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws4ta_bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws4ta_bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:layout-panel-left-solid" {...props}></Icon>
