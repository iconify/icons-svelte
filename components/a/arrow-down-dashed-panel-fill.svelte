<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypoifcync.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypoifcync"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-dashed-panel-fill" {...props}></Icon>
