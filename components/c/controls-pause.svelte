<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1-wfq4rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1-wfq4rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:controls-pause" {...props}></Icon>
