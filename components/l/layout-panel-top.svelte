<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq1w66ubm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq1w66ubm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layout-panel-top" {...props}></Icon>
