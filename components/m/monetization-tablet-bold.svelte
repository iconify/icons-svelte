<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3l6mhb4c.css';
import '../../css/q/qoes-qt6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3l6mhb4c"/><path class="qoes-qt6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:monetization-tablet-bold" {...props}></Icon>
