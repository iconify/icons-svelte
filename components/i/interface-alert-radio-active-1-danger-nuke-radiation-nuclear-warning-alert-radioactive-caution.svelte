<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykhg1_noq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ykhg1_noq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-alert-radio-active-1-danger-nuke-radiation-nuclear-warning-alert-radioactive-caution" {...props}></Icon>
