<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjr09ebid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjr09ebid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-turkish-lira-solid" {...props}></Icon>
